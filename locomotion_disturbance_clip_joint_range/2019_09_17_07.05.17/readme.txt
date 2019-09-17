max-test-time: 10
max-episode-num: 5000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-l2-reg: 0.0003
interpolation: False
replay-buffer-size: 1000000
joint-interpolation: True
replay-start-size: 10000
prioritized-exp-replay: True
actor-weight-decay: 1e-06
env-id: HumanoidBalanceFilter-v0
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
max-path-step: 5000
actor-activation-fn: ['relu', 'relu', 'None']
HLC-frequency: 25
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
LLC-frequency: 500
expert-num: 4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
filter-torque: False
max-train-time: 10
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
critic-lr: 0.0003
dsr-gait-period: 0.6
epoch-num: 500
gating-index: None
action-dim: 12
state-dim: 23
loss-output-bound-coeff: 0.0
epoch-step-num: 5000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
task-weight: 0.5
critic-weight-decay: 1e-06
max-path-num: 20
max-step-num: 2500000000
bullet-default-PD: False
train-step-num: 1
batch-size: 128
critic-l2-reg: 0.0003
gating-layer-size: [32, 32]
critic-activation-fn: ['relu', 'relu', 'None']
imitation-weight: 0.5
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
total-step-num: 2500000000
tau: 0.001
rollout-step-num: 1
loss-output-diff-coeff: 0
reward-scale: 0.1
render-eval: False
critic-layer-size: [256, 256]
squash-action: True
dsr-gait-freq: 1.667
loss-entropy-coeff: 0.0
gamma: 0.955
actor-layer-size: [256, 256]
Physics-frequency: 1000
loss-output-smooth-coeff: 0.5
gating-activation-fn: ['relu', 'relu', 'None']
test-num: 4
replay-ratio: 1
actor-lr: 0.0003
expert-index: None
record-start-size: 10000.0
n-step: 1
