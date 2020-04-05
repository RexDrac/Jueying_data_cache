critic-weight-decay: 1e-06
loss-output-smooth-coeff: 2.0
actor-l2-reg: 0.0003
epoch-num: 500
actor-layer-size: [256, 256]
max-path-step: 5000
task-weight: 0.5
state-dim: 23
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-test-time: 10
filter-torque: False
rollout-step-num: 1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
gating-layer-size: [32, 32]
loss-entropy-coeff: 0.0
bullet-default-PD: False
loss-output-diff-coeff: 0
train-step-num: 1
gamma: 0.955
Physics-frequency: 1000
interpolation: False
critic-l2-reg: 0.0003
dsr-gait-period: 0.6
max-path-num: 20
record-start-size: 10000.0
replay-start-size: 10000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
test-num: 4
max-step-num: 2500000000
replay-buffer-size: 1000000
critic-layer-size: [256, 256]
replay-ratio: 1
render-eval: False
total-step-num: 2500000000
expert-num: 4
loss-output-bound-coeff: 0.0
critic-lr: 0.0003
HLC-frequency: 25
dsr-gait-freq: 1.667
actor-weight-decay: 1e-06
LLC-frequency: 500
filter-action: True
gating-activation-fn: ['relu', 'relu', 'None']
gating-index: None
batch-size: 128
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
max-episode-num: 5000000
expert-index: None
env-id: HumanoidBalanceFilter-v0
actor-lr: 0.0003
tau: 0.001
actor-activation-fn: ['relu', 'relu', 'None']
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
imitation-weight: 0.5
epoch-step-num: 5000000
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
n-step: 1
squash-action: True
critic-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
max-train-time: 10
reward-scale: 0.1
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
prioritized-exp-replay: True
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
