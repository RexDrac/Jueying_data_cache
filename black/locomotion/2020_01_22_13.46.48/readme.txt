epoch-num: 500
expert-num: 4
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
state-dim: 23
train-step-num: 1
imitation-weight: 0.5
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
gating-index: None
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
env-id: HumanoidBalanceFilter-v0
max-path-num: 20
test-num: 4
max-step-num: 2500000000
task-weight: 0.5
replay-start-size: 10000
bullet-default-PD: False
total-step-num: 2500000000
filter-torque: False
Physics-frequency: 1000
max-episode-num: 5000000
actor-l2-reg: 0.0003
epoch-step-num: 5000000
tau: 0.001
n-step: 1
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
render-eval: False
actor-layer-size: [256, 256]
HLC-frequency: 25
categorical-distribution: {'v_min': -10, 'v_max': 250, 'n_atoms': 51}
record-start-size: 10000.0
critic-activation-fn: ['relu', 'relu', 'None']
max-path-step: 5000
expert-index: None
reward-scale: 0.1
replay-buffer-size: 1000000
actor-activation-fn: ['relu', 'relu', 'None']
critic-l2-reg: 0.0003
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
action-dim: 12
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
interpolation: False
LLC-frequency: 500
filter-action: True
batch-size: 128
joint-interpolation: True
critic-layer-size: [256, 256]
loss-entropy-coeff: 0.0
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-bound-coeff: 0.0
rollout-step-num: 1
dsr-gait-freq: 1.667
actor-lr: 0.0003
gating-layer-size: [32, 32]
loss-output-diff-coeff: 0
loss-output-smooth-coeff: 2.0
squash-action: True
prioritized-exp-replay: True
max-train-time: 10
actor-weight-decay: 1e-06
critic-weight-decay: 1e-06
dsr-gait-period: 0.6
replay-ratio: 1
gamma: 0.955
critic-lr: 0.0003
max-test-time: 10
